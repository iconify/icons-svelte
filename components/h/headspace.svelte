<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpws0u1gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpws0u1gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:headspace" {...props}></Icon>
