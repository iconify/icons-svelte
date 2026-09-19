<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-yb0tb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k-yb0tb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mariadb-wordmark" {...props}></Icon>
