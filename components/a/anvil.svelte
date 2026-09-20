<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n14bc-byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n14bc-byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:anvil" {...props}></Icon>
