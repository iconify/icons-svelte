<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4o22cjfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4o22cjfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:middleware" {...props}></Icon>
