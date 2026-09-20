<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj9mmeb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj9mmeb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:burncloud" {...props}></Icon>
