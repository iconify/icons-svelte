<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ienuj02sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ienuj02sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mongodb-outline" {...props}></Icon>
