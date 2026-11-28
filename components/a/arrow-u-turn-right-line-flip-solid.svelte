<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekf6tmb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekf6tmb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-right-line-flip-solid" {...props}></Icon>
