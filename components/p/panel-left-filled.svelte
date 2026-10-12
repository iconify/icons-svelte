<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hchuaz8ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hchuaz8ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-left-filled" {...props}></Icon>
