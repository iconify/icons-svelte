<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy-gc10hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sy-gc10hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:microscope-filled" {...props}></Icon>
