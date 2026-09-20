<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onw3tixkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onw3tixkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:carrd" {...props}></Icon>
