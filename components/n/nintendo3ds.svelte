<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaa7zvtxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa7zvtxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nintendo3ds" {...props}></Icon>
