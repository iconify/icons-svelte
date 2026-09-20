<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir6jv9c4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ir6jv9c4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-forest-service" {...props}></Icon>
