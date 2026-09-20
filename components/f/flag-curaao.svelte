<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/codjm1acu.css';
import '../../css/k/kxwpsgb3y.css';
import '../../css/m/mwd0dodcu.css';
import '../../css/q/qhkx3jbxs.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="codjm1acu"/><path class="kxwpsgb3y"/><path class="mwd0dodcu"/><path class="qhkx3jbxs"/><g><path class="qy525jbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-curaao" {...props}></Icon>
