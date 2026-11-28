<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf8cknr0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wf8cknr0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plus-duotone" {...props}></Icon>
