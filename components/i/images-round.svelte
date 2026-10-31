<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt68ehb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt68ehb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:images-round" {...props}></Icon>
