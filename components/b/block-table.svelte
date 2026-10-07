<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li1kmjboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li1kmjboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:block-table" {...props}></Icon>
