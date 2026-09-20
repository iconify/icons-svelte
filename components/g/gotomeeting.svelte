<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1nli6baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1nli6baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gotomeeting" {...props}></Icon>
