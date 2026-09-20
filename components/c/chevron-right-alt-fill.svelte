<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_nt6zbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_nt6zbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-right-alt-fill" {...props}></Icon>
