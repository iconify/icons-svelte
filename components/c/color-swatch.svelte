<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1xsz1bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1xsz1bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:color-swatch" {...props}></Icon>
