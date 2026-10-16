<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oanyu-b7f.css';
import '../../css/a/aq7lsdb9w.css';
import '../../css/m/mbsy57b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oanyu-b7f"/><path class="aq7lsdb9w"/><path class="mbsy57b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:assembly-line-48-bold" {...props}></Icon>
