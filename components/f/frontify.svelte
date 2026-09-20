<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvugj5xzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvugj5xzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:frontify" {...props}></Icon>
