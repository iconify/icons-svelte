<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdgw8wb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdgw8wb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:clipboard-document-list" {...props}></Icon>
