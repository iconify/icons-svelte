<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp3iq2bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cp3iq2bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-fold-down-left" {...props}></Icon>
