<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz6q-0bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz6q-0bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mediamarkt" {...props}></Icon>
