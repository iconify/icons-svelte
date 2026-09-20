<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8r1eubvq.css';
import '../../css/c/c4qk6y-3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8r1eubvq"/><path class="c4qk6y-3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gzil" {...props}></Icon>
