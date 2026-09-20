<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfot2jebo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kfot2jebo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-skip-forward" {...props}></Icon>
