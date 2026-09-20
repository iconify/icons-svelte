<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weyd5pbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weyd5pbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:clef-alto" {...props}></Icon>
