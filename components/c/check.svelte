<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ojfcb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ojfcb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:check" {...props}></Icon>
