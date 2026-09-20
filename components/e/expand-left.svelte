<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aze3fnbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aze3fnbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:expand-left" {...props}></Icon>
