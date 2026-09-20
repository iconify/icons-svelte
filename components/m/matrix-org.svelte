<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq41gqsbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq41gqsbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:matrix-org" {...props}></Icon>
