<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hflsuxw7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hflsuxw7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:praying-hands" {...props}></Icon>
