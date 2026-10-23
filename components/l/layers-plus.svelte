<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkry21_9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkry21_9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layers-plus" {...props}></Icon>
