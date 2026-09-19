<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idhihzbba.css';
import '../../css/g/g3esovain.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="idhihzbba"/><path class="g3esovain"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-skip-forward" {...props}></Icon>
