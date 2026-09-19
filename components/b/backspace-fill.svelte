<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzhqgcr0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzhqgcr0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:backspace-fill" {...props}></Icon>
