<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/d/d410gj.css';
import '../../css/j/j05t1v.css';
import '../../css/s/so-from-18.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c d410gj"/><path class="a0m25c j05t1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:fork-right" {...props}></Icon>
