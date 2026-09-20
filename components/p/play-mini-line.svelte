<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi76c70-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi76c70-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-mini-line" {...props}></Icon>
