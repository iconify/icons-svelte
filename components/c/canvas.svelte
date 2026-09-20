<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joe1tcclw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joe1tcclw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:canvas" {...props}></Icon>
