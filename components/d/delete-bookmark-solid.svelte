<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u28bdqbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u28bdqbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-bookmark-solid" {...props}></Icon>
