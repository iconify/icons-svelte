<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlj8iblgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlj8iblgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-pop" {...props}></Icon>
