<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avq__8bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avq__8bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:code-xml" {...props}></Icon>
