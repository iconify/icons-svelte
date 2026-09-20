<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn-sj6b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn-sj6b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-five" {...props}></Icon>
