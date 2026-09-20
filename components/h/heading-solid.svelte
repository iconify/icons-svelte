<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy-727bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy-727bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-solid" {...props}></Icon>
