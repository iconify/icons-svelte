<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_mvju3ef.css';
import '../../css/h/h_1n0zf8d.css';
import '../../css/t/tik2kabvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="f_mvju3ef"/><path class="h_1n0zf8d"/><path class="tik2kabvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netalertx" {...props}></Icon>
