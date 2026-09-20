<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpjlox1qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpjlox1qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:achievement-outline" {...props}></Icon>
