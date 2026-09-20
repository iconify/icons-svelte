<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1ncy95lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ncy95lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fast-forward" {...props}></Icon>
