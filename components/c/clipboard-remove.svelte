<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsmf7uamc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsmf7uamc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clipboard-remove" {...props}></Icon>
