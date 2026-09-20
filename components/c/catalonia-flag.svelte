<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dur0b2p3t.css';
import '../../css/n/n_h3l4baj.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="n_h3l4baj"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:catalonia-flag" {...props}></Icon>
