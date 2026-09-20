<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq06-391u.css';
import '../../css/r/rte4cibeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yq06-391u"/><path class="rte4cibeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:abt" {...props}></Icon>
