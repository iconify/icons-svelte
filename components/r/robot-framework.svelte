<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z14493pec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z14493pec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:robot-framework" {...props}></Icon>
