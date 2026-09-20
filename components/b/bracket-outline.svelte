<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6k0cjx2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d6k0cjx2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bracket-outline" {...props}></Icon>
