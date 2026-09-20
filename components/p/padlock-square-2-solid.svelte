<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ba2lbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0ba2lbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:padlock-square-2-solid" {...props}></Icon>
