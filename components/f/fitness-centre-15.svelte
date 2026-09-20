<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8frt8zje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o8frt8zje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fitness-centre-15" {...props}></Icon>
