<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtqm7xbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vtqm7xbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gimp" {...props}></Icon>
