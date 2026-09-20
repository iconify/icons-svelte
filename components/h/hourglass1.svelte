<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnthnnzvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gnthnnzvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass1" {...props}></Icon>
