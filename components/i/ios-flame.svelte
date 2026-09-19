<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_dbknkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw_dbknkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flame" {...props}></Icon>
