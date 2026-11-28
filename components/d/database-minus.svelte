<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr2d92ppj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr2d92ppj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-minus" {...props}></Icon>
