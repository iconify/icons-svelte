<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5yc4abgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5yc4abgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ban-fill" {...props}></Icon>
