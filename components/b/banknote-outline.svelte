<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_qbl-6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md_qbl-6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-outline" {...props}></Icon>
