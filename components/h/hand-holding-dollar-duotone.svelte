<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs7bwc8re.css';
import '../../css/w/wirx_bx0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs7bwc8re"/><path clip-rule="evenodd" class="wirx_bx0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hand-holding-dollar-duotone" {...props}></Icon>
