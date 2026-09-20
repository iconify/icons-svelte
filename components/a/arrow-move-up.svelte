<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajdm0abav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajdm0abav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-up" {...props}></Icon>
