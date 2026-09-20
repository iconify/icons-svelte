<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-6kbbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj-6kbbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:desktop-slash" {...props}></Icon>
