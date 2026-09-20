<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrhh4yzcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrhh4yzcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:battery-full" {...props}></Icon>
