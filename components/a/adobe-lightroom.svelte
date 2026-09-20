<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa47n1b8j.css';
import '../../css/f/fkrgg3o2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pa47n1b8j"/><path class="fkrgg3o2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-lightroom" {...props}></Icon>
