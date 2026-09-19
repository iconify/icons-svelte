<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljd0xbcvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ljd0xbcvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:abbr-ql" {...props}></Icon>
