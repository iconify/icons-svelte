<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jayktdbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jayktdbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reload-fill-round" {...props}></Icon>
