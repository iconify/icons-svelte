<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy-u42bhp.css';
import '../../css/b/bkoar43ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zy-u42bhp"/><path class="bkoar43ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-check-48-bold" {...props}></Icon>
