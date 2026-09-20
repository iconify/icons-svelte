<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/e/ehh26n.css';
import '../../css/a/asf8ox.css';
import '../../css/s/so-from-28.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ehh26n"/><path class="a0m25c asf8ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:account" {...props}></Icon>
