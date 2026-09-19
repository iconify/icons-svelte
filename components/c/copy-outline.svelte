<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh9q8b7lx.css';
import '../../css/g/gtdmtvp5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh9q8b7lx"/><path class="gtdmtvp5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:copy-outline" {...props}></Icon>
