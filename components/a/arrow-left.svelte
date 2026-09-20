<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/p/pkg6ma.css';
import '../../css/e/ewwyqq.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c pkg6ma"/><path class="a0m25c ewwyqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-left" {...props}></Icon>
