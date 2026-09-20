<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arpkf7b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arpkf7b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-up-filled" {...props}></Icon>
