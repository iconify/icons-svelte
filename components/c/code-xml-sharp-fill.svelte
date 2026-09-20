<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sro2fub8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sro2fub8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:code-xml-sharp-fill" {...props}></Icon>
