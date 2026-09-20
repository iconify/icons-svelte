<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr4rj9b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr4rj9b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:padlock-shield-remix" {...props}></Icon>
