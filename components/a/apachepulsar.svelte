<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exjf98b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exjf98b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachepulsar" {...props}></Icon>
