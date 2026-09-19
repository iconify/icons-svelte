<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imxv1m5kb.css';
import '../../css/t/t8iobcbuq.css';
import '../../css/l/l0krix3kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imxv1m5kb"/><path class="t8iobcbuq"/><path class="l0krix3kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:playstation" {...props}></Icon>
