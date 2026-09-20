<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nor8u-b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nor8u-b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:framer-outline" {...props}></Icon>
