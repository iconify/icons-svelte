<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vovlo1rpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vovlo1rpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:neer" {...props}></Icon>
