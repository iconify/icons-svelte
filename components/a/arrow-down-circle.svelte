<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/p/p0bift.css';
import '../../css/a/a-v8cn.css';
import '../../css/o/osy4ff.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c p0bift"/><path class="a-v8cn a0m25c"/><path class="a0m25c osy4ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-down-circle" {...props}></Icon>
