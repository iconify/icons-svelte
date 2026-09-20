<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb_59lfpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cb_59lfpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-solid" {...props}></Icon>
