<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3qnx6z1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3qnx6z1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:checkbox" {...props}></Icon>
