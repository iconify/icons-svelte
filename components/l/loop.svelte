<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h04f6kb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h04f6kb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:loop" {...props}></Icon>
