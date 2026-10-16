<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3-57bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm3-57bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:merge" {...props}></Icon>
