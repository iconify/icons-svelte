<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu4u9_s1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4u9_s1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:papermc" {...props}></Icon>
