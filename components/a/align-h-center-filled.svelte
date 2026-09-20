<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnb-kjcok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnb-kjcok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-h-center-filled" {...props}></Icon>
