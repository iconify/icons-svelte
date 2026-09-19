<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx7oyrbof.css';
import '../../css/m/mb0x8lb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dx7oyrbof"/><path class="mb0x8lb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:info-filled" {...props}></Icon>
