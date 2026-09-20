<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqh3gbb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh3gbb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-up-filled" {...props}></Icon>
