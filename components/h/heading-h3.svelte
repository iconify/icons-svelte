<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfusfgb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfusfgb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:heading-h3" {...props}></Icon>
