<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hd0z9c.css';
import '../../css/x/x7axda.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hd0z9c"/><path class="a0m25c x7axda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-double-down" {...props}></Icon>
