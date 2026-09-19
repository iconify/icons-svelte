<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wisswdjix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wisswdjix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:badge-fill" {...props}></Icon>
