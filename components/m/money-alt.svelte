<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oez7e4bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oez7e4bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:money-alt" {...props}></Icon>
