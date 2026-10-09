<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30s81bis.css';
import '../../css/b/bgmrj3pax.css';
import '../../css/w/wx83d8hml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y30s81bis"/><path class="bgmrj3pax"/><path class="wx83d8hml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biogas-digester-20" {...props}></Icon>
