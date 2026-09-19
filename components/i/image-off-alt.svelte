<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxejc3bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxejc3bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-off-alt" {...props}></Icon>
