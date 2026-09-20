<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om12kcc9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om12kcc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:css3" {...props}></Icon>
