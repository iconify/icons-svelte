<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/q/q9f3-p.css';
import '../../css/z/zaa6zm.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c q9f3-p"/><path class="a0m25c zaa6zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:double-arrow-vertical" {...props}></Icon>
