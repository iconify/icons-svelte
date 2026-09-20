<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6psufbgn.css';
import '../../css/c/ck6gfpkya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6psufbgn"/><path class="ck6gfpkya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pai" {...props}></Icon>
