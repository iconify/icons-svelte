<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr8crrw1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nr8crrw1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cafe" {...props}></Icon>
