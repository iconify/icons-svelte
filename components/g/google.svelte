<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al903vbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al903vbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:google" {...props}></Icon>
