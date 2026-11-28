<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol23xwbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol23xwbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-one-solid" {...props}></Icon>
