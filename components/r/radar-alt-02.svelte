<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w58vlgbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w58vlgbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:radar-alt-02" {...props}></Icon>
