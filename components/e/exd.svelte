<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t253e1abv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t253e1abv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:exd" {...props}></Icon>
