<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_2pqsbdw.css';
import '../../css/e/et2f85cnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j_2pqsbdw"/><path class="et2f85cnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pound-48-bold" {...props}></Icon>
