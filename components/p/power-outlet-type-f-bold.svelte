<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyvcxbgtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wyvcxbgtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:power-outlet-type-f-bold" {...props}></Icon>
