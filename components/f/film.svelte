<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpkd6tnhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpkd6tnhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:film" {...props}></Icon>
