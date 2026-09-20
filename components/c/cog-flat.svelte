<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8ycm8llg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n8ycm8llg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cog-flat" {...props}></Icon>
