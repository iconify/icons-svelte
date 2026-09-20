<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uix0dubku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uix0dubku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:android-studio" {...props}></Icon>
