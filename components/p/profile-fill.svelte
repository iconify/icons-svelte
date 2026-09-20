<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk2ma36ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk2ma36ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:profile-fill" {...props}></Icon>
