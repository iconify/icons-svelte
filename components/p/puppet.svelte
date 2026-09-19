<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aldf9vb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":335,"height":512};
const content = `<path class="aldf9vb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:puppet" {...props}></Icon>
