<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqvr3s70x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqvr3s70x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-left-outline" {...props}></Icon>
