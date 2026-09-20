<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftt6qlmpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftt6qlmpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:curl" {...props}></Icon>
