<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjh-wu7-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wjh-wu7-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-left-f" {...props}></Icon>
