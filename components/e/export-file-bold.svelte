<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2j4griqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2j4griqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:export-file-bold" {...props}></Icon>
