<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tokno44rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tokno44rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beaker-alt-filled" {...props}></Icon>
