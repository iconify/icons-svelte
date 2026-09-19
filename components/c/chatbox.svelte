<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya5otobje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya5otobje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbox" {...props}></Icon>
