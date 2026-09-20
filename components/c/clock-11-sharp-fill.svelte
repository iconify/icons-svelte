<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9l-ukbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9l-ukbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-11-sharp-fill" {...props}></Icon>
