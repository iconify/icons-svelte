<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0bkqib-z.css';
import '../../css/h/h9ba1ntbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0bkqib-z"/><path class="h9ba1ntbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:professions-man-astronaut-bold" {...props}></Icon>
