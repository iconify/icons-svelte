<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar9d4uk4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar9d4uk4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-nodejs" {...props}></Icon>
