<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z47l6_8sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z47l6_8sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:picpay" {...props}></Icon>
