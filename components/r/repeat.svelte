<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc0o0xwir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc0o0xwir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:repeat" {...props}></Icon>
