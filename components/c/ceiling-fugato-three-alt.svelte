<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zma5sabei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zma5sabei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-fugato-three-alt" {...props}></Icon>
