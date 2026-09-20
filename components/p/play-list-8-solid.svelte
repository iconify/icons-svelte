<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6uwribyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6uwribyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:play-list-8-solid" {...props}></Icon>
