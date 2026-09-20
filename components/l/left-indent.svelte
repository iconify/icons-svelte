<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9435640u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9435640u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:left-indent" {...props}></Icon>
