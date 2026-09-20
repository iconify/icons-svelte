<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko4fmo4iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ko4fmo4iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-6" {...props}></Icon>
