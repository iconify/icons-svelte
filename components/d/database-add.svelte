<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilmixgbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ilmixgbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:database-add" {...props}></Icon>
