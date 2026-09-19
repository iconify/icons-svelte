<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/new38nbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="new38nbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:details-less" {...props}></Icon>
