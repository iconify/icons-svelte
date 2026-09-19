<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olr6uaclq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="olr6uaclq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:photoshop" {...props}></Icon>
