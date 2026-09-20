<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-5oz6bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-5oz6bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:katana" {...props}></Icon>
