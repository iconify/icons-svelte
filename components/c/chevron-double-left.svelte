<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/i/i7ci2f.css';
import '../../css/q/qe03jo.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c i7ci2f"/><path class="a0m25c qe03jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-double-left" {...props}></Icon>
