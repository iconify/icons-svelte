<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_kk2vjms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a_kk2vjms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cat-2-remix" {...props}></Icon>
