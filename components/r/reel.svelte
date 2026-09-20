<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe3f5lbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xe3f5lbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reel" {...props}></Icon>
