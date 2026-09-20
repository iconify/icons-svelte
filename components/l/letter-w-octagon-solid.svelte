<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxeiy3-qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxeiy3-qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-w-octagon-solid" {...props}></Icon>
