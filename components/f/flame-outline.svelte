<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg9nnwstw.css';
import '../../css/u/uz_ojxb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sg9nnwstw"/><path class="uz_ojxb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flame-outline" {...props}></Icon>
