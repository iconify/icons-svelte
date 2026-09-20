<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3nk_yjdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c3nk_yjdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-x-solid" {...props}></Icon>
