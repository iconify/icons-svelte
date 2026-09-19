<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/askbefb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="askbefb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:circle-arrow-left" {...props}></Icon>
