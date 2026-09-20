<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf-kwhb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hf-kwhb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:brain-bold" {...props}></Icon>
