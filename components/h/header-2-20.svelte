<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce19mdb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ce19mdb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:header-2-20" {...props}></Icon>
