<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1i2kqxtp.css';
import '../../css/z/zhydivsjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1i2kqxtp"/><path class="zhydivsjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:note-48" {...props}></Icon>
