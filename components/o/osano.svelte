<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1bla5bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1bla5bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:osano" {...props}></Icon>
