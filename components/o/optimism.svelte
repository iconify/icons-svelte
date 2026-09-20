<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zi1hiyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zi1hiyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:optimism" {...props}></Icon>
