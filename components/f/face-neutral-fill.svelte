<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6_2om8kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6_2om8kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-neutral-fill" {...props}></Icon>
