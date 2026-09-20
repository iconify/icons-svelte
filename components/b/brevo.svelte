<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sya7x0bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sya7x0bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:brevo" {...props}></Icon>
