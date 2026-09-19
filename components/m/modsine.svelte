<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcye5bblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qcye5bblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:modsine" {...props}></Icon>
