<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umjj1fa5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umjj1fa5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-ease-out-filled" {...props}></Icon>
