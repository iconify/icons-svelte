<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iobqtibmb.css';
import '../../css/m/mpwpx1vpl.css';
import '../../css/f/fk33t7eqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iobqtibmb"/><path class="mpwpx1vpl"/><path class="fk33t7eqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-database" {...props}></Icon>
