<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlcn_2b3l.css';
import '../../css/f/f7l70zbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dlcn_2b3l"/><path class="f7l70zbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pipe-fill" {...props}></Icon>
