<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miukfq3du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="miukfq3du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bank-outline" {...props}></Icon>
