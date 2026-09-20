<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj4xopbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj4xopbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kluster" {...props}></Icon>
