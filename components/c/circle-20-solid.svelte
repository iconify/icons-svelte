<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufw4fv8xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ufw4fv8xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-20-solid" {...props}></Icon>
