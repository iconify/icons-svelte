<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/f/f3rx7t.css';
import '../../css/t/txuwiv.css';
import '../../css/y/yp-liy.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c f3rx7t"/><path class="a0m25c txuwiv"/><path class="a0m25c yp-liy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-align-middle" {...props}></Icon>
