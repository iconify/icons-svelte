<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flab64b9x.css';
import '../../css/e/eehn7s3el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flab64b9x"/><path class="eehn7s3el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fast-food-sharp" {...props}></Icon>
