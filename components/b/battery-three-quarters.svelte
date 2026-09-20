<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0mtshrrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="u0mtshrrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-three-quarters" {...props}></Icon>
