<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twh9358jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="twh9358jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-2-solid" {...props}></Icon>
