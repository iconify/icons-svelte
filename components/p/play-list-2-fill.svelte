<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugdzc4kwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugdzc4kwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-list-2-fill" {...props}></Icon>
