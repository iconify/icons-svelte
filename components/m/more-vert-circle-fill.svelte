<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcl0_1bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mcl0_1bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-vert-circle-fill" {...props}></Icon>
