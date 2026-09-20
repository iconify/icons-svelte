<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw063kx1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw063kx1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:blade-filled" {...props}></Icon>
