<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-xnubhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8-xnubhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:plus-five-circle" {...props}></Icon>
