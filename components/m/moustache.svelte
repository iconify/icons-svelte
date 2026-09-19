<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaw_6nhre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaw_6nhre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moustache" {...props}></Icon>
