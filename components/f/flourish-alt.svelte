<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go2yq50ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go2yq50ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:flourish-alt" {...props}></Icon>
