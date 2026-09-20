<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvf6hzvqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pvf6hzvqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:car-outline" {...props}></Icon>
