<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw74_bujk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mw74_bujk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:aircraft" {...props}></Icon>
