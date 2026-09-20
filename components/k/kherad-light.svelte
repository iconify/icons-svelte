<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxgn3kbue.css';
import '../../css/h/h-c75yrdf.css';
import '../../css/g/g953mjzjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxgn3kbue"/><path class="h-c75yrdf"/><path class="g953mjzjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kherad-light" {...props}></Icon>
