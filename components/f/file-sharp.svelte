<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjv-31b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjv-31b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-sharp" {...props}></Icon>
