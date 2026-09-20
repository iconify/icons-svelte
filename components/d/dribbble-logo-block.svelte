<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ril0c-ubp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ril0c-ubp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dribbble-logo-block" {...props}></Icon>
