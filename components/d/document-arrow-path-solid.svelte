<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjyan90lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjyan90lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-arrow-path-solid" {...props}></Icon>
