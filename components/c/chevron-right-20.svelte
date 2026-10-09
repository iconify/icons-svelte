<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfza-jq-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gfza-jq-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-right-20" {...props}></Icon>
