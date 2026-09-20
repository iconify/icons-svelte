<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbd2hib5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lbd2hib5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:coffee" {...props}></Icon>
