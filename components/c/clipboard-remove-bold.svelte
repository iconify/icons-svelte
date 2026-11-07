<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvxlsjb-h.css';
import '../../css/f/f4wux_7ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxlsjb-h"/><path clip-rule="evenodd" class="f4wux_7ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-remove-bold" {...props}></Icon>
