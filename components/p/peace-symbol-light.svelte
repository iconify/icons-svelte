<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0huabc9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0huabc9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:peace-symbol-light" {...props}></Icon>
