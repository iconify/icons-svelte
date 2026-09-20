<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j36jq6bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j36jq6bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-cloud-line" {...props}></Icon>
