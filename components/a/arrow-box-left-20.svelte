<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5sc-_b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s5sc-_b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-box-left-20" {...props}></Icon>
