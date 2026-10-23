<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q00mw2byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q00mw2byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-down-up" {...props}></Icon>
