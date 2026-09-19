<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk9lgc8st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zk9lgc8st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:object-ungroup-outline" {...props}></Icon>
