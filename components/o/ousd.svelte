<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4-wcftdv.css';
import '../../css/x/x4rg6acqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4-wcftdv"/><path clip-rule="evenodd" class="x4rg6acqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ousd" {...props}></Icon>
