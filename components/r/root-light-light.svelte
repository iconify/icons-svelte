<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bajjv5bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bajjv5bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:root-light-light" {...props}></Icon>
