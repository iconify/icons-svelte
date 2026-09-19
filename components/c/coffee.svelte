<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7jhd1bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":448};
const content = `<path class="s7jhd1bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:coffee" {...props}></Icon>
