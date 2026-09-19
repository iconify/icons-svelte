<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk5rj2xsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mk5rj2xsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:no-smoking" {...props}></Icon>
