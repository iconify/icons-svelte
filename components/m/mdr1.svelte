<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egd_w98el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egd_w98el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mdr1" {...props}></Icon>
