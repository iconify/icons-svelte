<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvxlsjb-h.css';
import '../../css/f/f7qo9xbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxlsjb-h"/><path clip-rule="evenodd" class="f7qo9xbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-add-bold" {...props}></Icon>
