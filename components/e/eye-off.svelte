<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum74s82r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oum74s82r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eye-off" {...props}></Icon>
