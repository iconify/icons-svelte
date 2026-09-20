<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udxk9scsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udxk9scsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:podcast" {...props}></Icon>
