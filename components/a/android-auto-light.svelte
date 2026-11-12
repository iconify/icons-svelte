<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6taebzo.css';
import '../../css/c/c991nybxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd6taebzo"/><path class="c991nybxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-auto-light" {...props}></Icon>
