<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-czv9j6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j-czv9j6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-object-bottom-solid" {...props}></Icon>
