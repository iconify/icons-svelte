<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjriywbzo.css';
import '../../css/a/acxc33bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjriywbzo"/><path class="acxc33bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copy-x-filled" {...props}></Icon>
