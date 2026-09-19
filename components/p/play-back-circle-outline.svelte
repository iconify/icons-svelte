<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld5kc0m-n.css';
import '../../css/b/bblqfdb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ld5kc0m-n"/><path class="bblqfdb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-back-circle-outline" {...props}></Icon>
