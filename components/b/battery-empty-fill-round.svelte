<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubv0g8btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubv0g8btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-empty-fill-round" {...props}></Icon>
