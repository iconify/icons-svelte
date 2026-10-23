<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl4f5wabm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4f5wabm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:factory" {...props}></Icon>
