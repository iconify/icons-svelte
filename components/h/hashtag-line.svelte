<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6ue0qncj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6ue0qncj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hashtag-line" {...props}></Icon>
