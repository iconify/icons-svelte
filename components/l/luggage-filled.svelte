<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-itl9ibz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-itl9ibz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:luggage-filled" {...props}></Icon>
