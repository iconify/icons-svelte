<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlxs1tz2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mlxs1tz2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ab-testing-outline" {...props}></Icon>
