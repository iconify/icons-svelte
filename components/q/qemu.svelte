<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pruczugwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pruczugwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qemu" {...props}></Icon>
