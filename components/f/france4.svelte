<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br9ibdxxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br9ibdxxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:france4" {...props}></Icon>
