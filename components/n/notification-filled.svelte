<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo_eismww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_eismww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-filled" {...props}></Icon>
