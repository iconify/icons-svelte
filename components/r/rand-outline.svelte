<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjx4ulw2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jjx4ulw2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rand-outline" {...props}></Icon>
