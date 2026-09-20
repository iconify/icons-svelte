<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upd0nac5h.css';
import '../../css/z/zce1ctb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="upd0nac5h"/><path class="zce1ctb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nym" {...props}></Icon>
