<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlh-g9eso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlh-g9eso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:food" {...props}></Icon>
