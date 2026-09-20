<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsmuf-bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fsmuf-bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-low-filled" {...props}></Icon>
