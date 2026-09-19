<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln5b_cbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1027,"height":1026};
const content = `<path class="ln5b_cbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rorschach" {...props}></Icon>
