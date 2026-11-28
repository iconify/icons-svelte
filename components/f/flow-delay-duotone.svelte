<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9w83dibl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9w83dibl primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-delay-duotone" {...props}></Icon>
