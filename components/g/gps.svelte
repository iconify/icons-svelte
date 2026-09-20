<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa8z4qbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1};
const content = `<path class="qa8z4qbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gps" {...props}></Icon>
