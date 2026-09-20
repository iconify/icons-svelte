<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avh6a8bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="avh6a8bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fix" {...props}></Icon>
