<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia73cybmz.css';
import '../../css/c/ccy637b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ia73cybmz"/><path class="ccy637b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:credit-card" {...props}></Icon>
