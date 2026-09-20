<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uko8-ubwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uko8-ubwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-asterisk" {...props}></Icon>
