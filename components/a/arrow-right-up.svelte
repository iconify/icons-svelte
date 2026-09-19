<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eozj1cb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eozj1cb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:arrow-right-up" {...props}></Icon>
