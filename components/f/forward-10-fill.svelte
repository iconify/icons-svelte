<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irz_gyb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="irz_gyb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:forward-10-fill" {...props}></Icon>
