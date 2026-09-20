<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud_d7qycl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud_d7qycl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:asus" {...props}></Icon>
