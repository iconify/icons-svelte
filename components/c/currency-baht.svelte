<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugf5aoo1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugf5aoo1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-baht" {...props}></Icon>
