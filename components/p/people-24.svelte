<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raj7bybid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raj7bybid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:people-24" {...props}></Icon>
