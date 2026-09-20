<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/p/p0fosk.css';
import '../../css/j/j-t5du.css';
import '../../css/s/so-from-14.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c p0fosk"/><path class="a0m25c j-t5du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:rotate-90" {...props}></Icon>
