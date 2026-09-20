<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouau9hbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouau9hbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cairo-metro" {...props}></Icon>
