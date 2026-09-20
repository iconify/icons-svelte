<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzab_8mca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzab_8mca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad3-filled" {...props}></Icon>
