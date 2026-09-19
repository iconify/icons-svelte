<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnux_zuii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jnux_zuii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:battery-full" {...props}></Icon>
