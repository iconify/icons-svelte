<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vff6l1ehp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vff6l1ehp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:password-bold" {...props}></Icon>
