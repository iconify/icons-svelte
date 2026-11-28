<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho7un-mez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho7un-mez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mail-heart" {...props}></Icon>
