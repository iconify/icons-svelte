<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c45xl7zgy.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c45xl7zgy"/><path class="hwjgqrbah"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-minus-48-bold" {...props}></Icon>
