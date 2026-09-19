<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cks-37igm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cks-37igm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:fur-affinity" {...props}></Icon>
