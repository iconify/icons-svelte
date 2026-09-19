<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faj9-9r7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faj9-9r7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cloud-upload" {...props}></Icon>
