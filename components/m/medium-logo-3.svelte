<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-6qnccdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-6qnccdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-3" {...props}></Icon>
