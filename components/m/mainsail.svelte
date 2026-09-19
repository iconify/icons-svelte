<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y36z6v4nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y36z6v4nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mainsail" {...props}></Icon>
