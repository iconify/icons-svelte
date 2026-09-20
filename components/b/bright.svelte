<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb84m8s8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb84m8s8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bright" {...props}></Icon>
