<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3bd7mocx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":959};
const content = `<path class="k3bd7mocx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dietwo" {...props}></Icon>
