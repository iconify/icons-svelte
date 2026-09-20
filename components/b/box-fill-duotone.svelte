<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tro4qhbhl.css';
import '../../css/y/y5a_feb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tro4qhbhl"/><path class="y5a_feb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:box-fill-duotone" {...props}></Icon>
