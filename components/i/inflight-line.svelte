<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5od4nixw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5od4nixw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:inflight-line" {...props}></Icon>
