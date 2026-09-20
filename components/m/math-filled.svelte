<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv8bute7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv8bute7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:math-filled" {...props}></Icon>
