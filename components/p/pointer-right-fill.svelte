<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppxr7-a6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppxr7-a6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pointer-right-fill" {...props}></Icon>
