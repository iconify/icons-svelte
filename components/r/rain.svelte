<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_c3ib5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pk_c3ib5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rain" {...props}></Icon>
