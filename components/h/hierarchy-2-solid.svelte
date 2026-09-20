<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfw-_u3sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfw-_u3sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-2-solid" {...props}></Icon>
