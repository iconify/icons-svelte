<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/d/d6imlv.css';
import '../../css/v/vx_7fa.css';
import '../../css/s/so-from-82.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c d6imlv"/><path class="a0m25c vx_7fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:mastodon" {...props}></Icon>
