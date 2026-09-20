<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhwrucx5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bhwrucx5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:micro-sd-card-outline" {...props}></Icon>
