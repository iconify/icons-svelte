<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcxmw9bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcxmw9bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lens" {...props}></Icon>
