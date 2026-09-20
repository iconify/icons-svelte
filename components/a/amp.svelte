<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt9swpb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt9swpb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amp" {...props}></Icon>
