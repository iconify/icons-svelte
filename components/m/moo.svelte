<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma00hrdix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma00hrdix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:moo" {...props}></Icon>
