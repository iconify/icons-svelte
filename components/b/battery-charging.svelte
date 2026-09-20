<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft_j2-bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_j2-bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-charging" {...props}></Icon>
