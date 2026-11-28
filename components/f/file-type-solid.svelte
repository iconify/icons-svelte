<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gydi2jbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gydi2jbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-type-solid" {...props}></Icon>
