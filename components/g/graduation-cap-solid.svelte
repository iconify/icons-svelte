<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx6-67b-c.css';
import '../../css/h/hk-cwxbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx6-67b-c"/><path class="hk-cwxbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:graduation-cap-solid" {...props}></Icon>
