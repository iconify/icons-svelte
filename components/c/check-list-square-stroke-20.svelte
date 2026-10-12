<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldh8llb9w.css';
import '../../css/o/o8vspab8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ldh8llb9w"/><path class="o8vspab8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-list-square-stroke-20" {...props}></Icon>
