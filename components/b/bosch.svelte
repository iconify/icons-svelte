<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-dnjzh7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-dnjzh7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bosch" {...props}></Icon>
