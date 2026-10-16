<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un_01ximz.css';
import '../../css/m/m4rbgbbhm.css';
import '../../css/q/qzowdsb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="un_01ximz"/><path class="m4rbgbbhm"/><path class="qzowdsb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-outgoing-48" {...props}></Icon>
