<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v51u0wbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v51u0wbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:house-user" {...props}></Icon>
