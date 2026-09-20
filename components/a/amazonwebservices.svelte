<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abc0zxb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abc0zxb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonwebservices" {...props}></Icon>
