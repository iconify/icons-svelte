<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dysvs-brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dysvs-brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-top-filled" {...props}></Icon>
