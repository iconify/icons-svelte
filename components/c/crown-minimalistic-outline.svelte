<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkfdtzbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkfdtzbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-outline" {...props}></Icon>
