<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aik-f7fra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aik-f7fra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:information" {...props}></Icon>
