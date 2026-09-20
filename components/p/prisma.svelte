<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q13ynob0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q13ynob0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:prisma" {...props}></Icon>
