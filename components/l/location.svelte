<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6u2ktsbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6u2ktsbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:location" {...props}></Icon>
