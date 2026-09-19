<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9xeebvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx9xeebvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-pin-off-fill" {...props}></Icon>
