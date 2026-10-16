<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg22kut3v.css';
import '../../css/o/ojajqfjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tg22kut3v"/><path class="ojajqfjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disconnector-48" {...props}></Icon>
