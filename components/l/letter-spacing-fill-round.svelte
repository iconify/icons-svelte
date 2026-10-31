<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvj7bob1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvj7bob1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-spacing-fill-round" {...props}></Icon>
