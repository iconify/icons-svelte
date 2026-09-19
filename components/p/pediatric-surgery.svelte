<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp9481b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gp9481b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pediatric-surgery" {...props}></Icon>
