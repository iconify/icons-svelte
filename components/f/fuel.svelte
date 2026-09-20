<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrwv1cbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lrwv1cbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fuel" {...props}></Icon>
