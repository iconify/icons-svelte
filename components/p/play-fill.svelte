<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spc0k281n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spc0k281n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:play-fill" {...props}></Icon>
