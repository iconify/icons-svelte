<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd6z39w7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd6z39w7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:photobucket" {...props}></Icon>
