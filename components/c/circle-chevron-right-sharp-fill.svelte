<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-r8iu1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-r8iu1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-right-sharp-fill" {...props}></Icon>
