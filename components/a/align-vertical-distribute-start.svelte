<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drp98crri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drp98crri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-distribute-start" {...props}></Icon>
