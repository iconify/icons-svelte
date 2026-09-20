<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj25gxyug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj25gxyug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:lock-alt" {...props}></Icon>
