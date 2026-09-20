<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7wes6u6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7wes6u6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clapperboard-line" {...props}></Icon>
