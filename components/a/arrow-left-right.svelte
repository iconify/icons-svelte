<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w96-qcbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w96-qcbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left-right" {...props}></Icon>
