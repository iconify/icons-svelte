<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzj8srv2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzj8srv2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-back-sharp" {...props}></Icon>
