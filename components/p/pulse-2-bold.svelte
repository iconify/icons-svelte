<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7423xb5z.css';
import '../../css/v/vd8i_6yln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7423xb5z"/><path class="vd8i_6yln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pulse-2-bold" {...props}></Icon>
