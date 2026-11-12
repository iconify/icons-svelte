<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzt09qmjr.css';
import '../../css/n/ny4v3jcym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzt09qmjr"/><path class="ny4v3jcym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perfice-dark" {...props}></Icon>
