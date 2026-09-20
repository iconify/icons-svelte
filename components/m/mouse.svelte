<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8-k7-a4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8-k7-a4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:mouse" {...props}></Icon>
