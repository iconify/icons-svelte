<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0k6b2b-n.css';
import '../../css/n/ndmpziulf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0k6b2b-n"/><path class="ndmpziulf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mushroom-filled" {...props}></Icon>
