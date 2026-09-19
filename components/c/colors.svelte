<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv6xttbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="lv6xttbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:colors" {...props}></Icon>
