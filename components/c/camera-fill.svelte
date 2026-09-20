<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7j41jzfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7j41jzfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:camera-fill" {...props}></Icon>
