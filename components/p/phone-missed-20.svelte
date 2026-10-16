<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf5oxvb8k.css';
import '../../css/z/zjz25chpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xf5oxvb8k"/><path class="zjz25chpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-missed-20" {...props}></Icon>
