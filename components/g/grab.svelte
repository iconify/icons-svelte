<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9q_cmbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a9q_cmbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:grab" {...props}></Icon>
