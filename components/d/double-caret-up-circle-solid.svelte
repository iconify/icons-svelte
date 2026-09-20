<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk5-6fd1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kk5-6fd1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-up-circle-solid" {...props}></Icon>
