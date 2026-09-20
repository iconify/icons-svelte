<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugrz9ubjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugrz9ubjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bug-light" {...props}></Icon>
