<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge1z230cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ge1z230cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lock-closed-sharp" {...props}></Icon>
