<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7iz5vvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7iz5vvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:hpe-labs" {...props}></Icon>
