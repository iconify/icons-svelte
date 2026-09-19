<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2g4xxswo.css';
import '../../css/d/doqrq2blo.css';
import '../../css/u/uf8ttfzhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2g4xxswo"/><path class="doqrq2blo"/><path class="uf8ttfzhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-build" {...props}></Icon>
