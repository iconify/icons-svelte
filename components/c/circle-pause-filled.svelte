<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no2d46b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no2d46b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-pause-filled" {...props}></Icon>
