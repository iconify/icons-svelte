<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyrziqb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyrziqb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-frown" {...props}></Icon>
