<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6fk_ut1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":392};
const content = `<path class="o6fk_ut1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:favorite" {...props}></Icon>
