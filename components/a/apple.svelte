<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbsyws46y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsyws46y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple" {...props}></Icon>
