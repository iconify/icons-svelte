<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta3eeokxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta3eeokxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pig-round" {...props}></Icon>
