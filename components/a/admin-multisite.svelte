<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mal-bixgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mal-bixgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-multisite" {...props}></Icon>
