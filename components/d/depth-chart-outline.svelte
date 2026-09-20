<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui3ma-bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ui3ma-bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:depth-chart-outline" {...props}></Icon>
