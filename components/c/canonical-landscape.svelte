<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejl9-ctos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejl9-ctos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:canonical-landscape" {...props}></Icon>
