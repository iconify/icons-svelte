<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvln8zfdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvln8zfdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autocannon" {...props}></Icon>
