<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da9y1yr3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="da9y1yr3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-horse" {...props}></Icon>
