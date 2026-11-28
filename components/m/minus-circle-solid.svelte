<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opmtvi5de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opmtvi5de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:minus-circle-solid" {...props}></Icon>
