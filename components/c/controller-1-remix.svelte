<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmyb5bbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zmyb5bbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:controller-1-remix" {...props}></Icon>
