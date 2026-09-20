<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmgtlccin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmgtlccin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-x-filled" {...props}></Icon>
