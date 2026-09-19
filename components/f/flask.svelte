<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz183ibfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz183ibfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:flask" {...props}></Icon>
