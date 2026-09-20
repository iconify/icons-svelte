<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfp4okqko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfp4okqko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-reload-horizontal-2-solid" {...props}></Icon>
