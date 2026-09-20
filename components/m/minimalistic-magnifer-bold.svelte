<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csocnccks.css';
import '../../css/l/llqf1f1jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csocnccks"/><path clip-rule="evenodd" class="llqf1f1jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-bold" {...props}></Icon>
