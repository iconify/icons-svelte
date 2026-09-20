<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/s/sclttp.css';
import '../../css/c/c9cwbe.css';
import '../../css/s/so-from-26.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c sclttp"/><path class="a0m25c c9cwbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:navigation-right-down" {...props}></Icon>
