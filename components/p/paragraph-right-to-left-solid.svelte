<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8f-i9b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8f-i9b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:paragraph-right-to-left-solid" {...props}></Icon>
