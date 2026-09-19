<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loo4nhxhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loo4nhxhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:label-important-filled" {...props}></Icon>
