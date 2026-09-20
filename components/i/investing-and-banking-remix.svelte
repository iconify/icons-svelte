<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doqujn1zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="doqujn1zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:investing-and-banking-remix" {...props}></Icon>
