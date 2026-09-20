<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibn--6bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibn--6bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x3-sharp-fill" {...props}></Icon>
