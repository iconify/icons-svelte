<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb1geub1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb1geub1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dashboard-circle" {...props}></Icon>
