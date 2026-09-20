<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/benixwbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="benixwbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:glovo" {...props}></Icon>
