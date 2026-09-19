<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiirhsbnc.css';
import '../../css/f/fsqj1k5yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiirhsbnc"/><path clip-rule="evenodd" class="fsqj1k5yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:login-outline" {...props}></Icon>
