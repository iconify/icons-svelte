<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjh0nmb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjh0nmb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-outline" {...props}></Icon>
