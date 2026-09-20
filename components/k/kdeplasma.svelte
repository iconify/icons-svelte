<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0pcspb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0pcspb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kdeplasma" {...props}></Icon>
