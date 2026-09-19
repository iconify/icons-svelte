<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjk7w0bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjk7w0bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:highbrightness" {...props}></Icon>
