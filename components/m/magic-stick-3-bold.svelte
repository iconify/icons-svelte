<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe050eb3u.css';
import '../../css/x/x8k8-5b4d.css';
import '../../css/z/zw138qb4j.css';
import '../../css/v/vbpdh7-jd.css';
import '../../css/r/ri-4y14ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe050eb3u"/><path class="x8k8-5b4d"/><path class="zw138qb4j"/><path class="vbpdh7-jd"/><path class="ri-4y14ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-stick-3-bold" {...props}></Icon>
