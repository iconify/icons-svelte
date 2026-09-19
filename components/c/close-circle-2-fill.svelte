<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmvbpub8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmvbpub8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-2-fill" {...props}></Icon>
