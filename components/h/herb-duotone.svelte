<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drijd_0ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drijd_0ya primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:herb-duotone" {...props}></Icon>
