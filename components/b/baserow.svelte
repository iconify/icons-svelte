<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukk32ff1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukk32ff1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:baserow" {...props}></Icon>
