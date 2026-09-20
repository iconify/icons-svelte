<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwg4w1bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iwg4w1bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:input-box-solid" {...props}></Icon>
