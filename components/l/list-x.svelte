<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynwb_uh6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynwb_uh6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:list-x" {...props}></Icon>
