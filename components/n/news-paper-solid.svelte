<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az07isbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="az07isbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:news-paper-solid" {...props}></Icon>
