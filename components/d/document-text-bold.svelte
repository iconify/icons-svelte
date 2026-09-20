<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq_g7xbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq_g7xbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-text-bold" {...props}></Icon>
