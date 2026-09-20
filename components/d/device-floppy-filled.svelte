<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs5gx7_kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs5gx7_kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-floppy-filled" {...props}></Icon>
