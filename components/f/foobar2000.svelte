<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujd44zd-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujd44zd-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:foobar2000" {...props}></Icon>
