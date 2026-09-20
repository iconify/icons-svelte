<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc7qydb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oc7qydb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:entrance" {...props}></Icon>
