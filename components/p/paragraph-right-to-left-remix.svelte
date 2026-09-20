<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6e5euaej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6e5euaej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:paragraph-right-to-left-remix" {...props}></Icon>
