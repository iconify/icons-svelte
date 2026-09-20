<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2pt2mban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="p2pt2mban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-small-solid" {...props}></Icon>
