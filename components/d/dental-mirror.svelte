<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz_w1whsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz_w1whsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dental-mirror" {...props}></Icon>
