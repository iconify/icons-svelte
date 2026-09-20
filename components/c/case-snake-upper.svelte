<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5le0mbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5le0mbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:case-snake-upper" {...props}></Icon>
