<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/f/fuzxbl.css';
import '../../css/r/rpw8kq.css';
import '../../css/s/so-from-8.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c fuzxbl"/><path class="a0m25c rpw8kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:computer" {...props}></Icon>
