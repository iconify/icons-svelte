<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qof5i9bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qof5i9bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy" {...props}></Icon>
