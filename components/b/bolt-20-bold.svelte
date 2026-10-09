<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqm7b_roe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jqm7b_roe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-20-bold" {...props}></Icon>
