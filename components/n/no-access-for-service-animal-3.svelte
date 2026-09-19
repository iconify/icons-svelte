<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u64em7bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u64em7bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-access-for-service-animal-3" {...props}></Icon>
