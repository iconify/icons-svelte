<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k88o-jb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k88o-jb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-octagon-solid" {...props}></Icon>
