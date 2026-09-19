<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emloct5vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emloct5vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:layout" {...props}></Icon>
