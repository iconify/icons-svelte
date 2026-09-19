<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-0g0bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-0g0bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:external-link" {...props}></Icon>
