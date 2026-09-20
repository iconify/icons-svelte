<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kab81ab2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kab81ab2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:acer" {...props}></Icon>
