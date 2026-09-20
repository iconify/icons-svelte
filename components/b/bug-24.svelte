<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy6lcguuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy6lcguuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bug-24" {...props}></Icon>
