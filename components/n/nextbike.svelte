<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4kgmb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4kgmb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nextbike" {...props}></Icon>
