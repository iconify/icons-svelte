<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dur0b2p3t.css';
import '../../css/l/lk8duns4e.css';
import '../../css/q/qh9qlceui.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="lk8duns4e"/><path class="qh9qlceui"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-colombia" {...props}></Icon>
