<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m22_0n6ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m22_0n6ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-remove-remix" {...props}></Icon>
