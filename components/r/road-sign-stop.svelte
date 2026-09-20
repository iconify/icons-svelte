<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4jp0udxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4jp0udxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-sign-stop" {...props}></Icon>
