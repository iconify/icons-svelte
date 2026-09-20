<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcqw2bbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcqw2bbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-generate-2" {...props}></Icon>
