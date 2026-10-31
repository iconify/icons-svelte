<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_appmbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_appmbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-left-fill-round" {...props}></Icon>
