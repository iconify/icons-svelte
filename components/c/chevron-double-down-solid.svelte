<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emug_9xpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emug_9xpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-double-down-solid" {...props}></Icon>
