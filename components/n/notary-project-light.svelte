<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhjqobksi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800};
const content = `<path class="lhjqobksi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:notary-project-light" {...props}></Icon>
