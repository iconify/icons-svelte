<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6k831oie.css';
import '../../css/r/rzbbq-lyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6k831oie"/><path class="rzbbq-lyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:memory-card-fill" {...props}></Icon>
