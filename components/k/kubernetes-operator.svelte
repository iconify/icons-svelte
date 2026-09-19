<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shykeihid.css';
import '../../css/o/ot-x0gcwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="shykeihid"/><path class="ot-x0gcwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kubernetes-operator" {...props}></Icon>
