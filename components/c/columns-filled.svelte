<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9kw14ayb.css';
import '../../css/w/wzt-b-bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="q9kw14ayb"/><rect class="wzt-b-bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:columns-filled" {...props}></Icon>
