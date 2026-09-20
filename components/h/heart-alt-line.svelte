<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrc_o7bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrc_o7bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:heart-alt-line" {...props}></Icon>
