<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq71m7b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq71m7b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:allocine" {...props}></Icon>
