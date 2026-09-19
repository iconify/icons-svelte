<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylgliubwh.css';
import '../../css/w/w-gbphaza.css';
import '../../css/v/vlmlzenit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ylgliubwh"/><path class="w-gbphaza"/><path class="vlmlzenit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:dash" {...props}></Icon>
