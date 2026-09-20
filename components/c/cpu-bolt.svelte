<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u70ysmltz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u70ysmltz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cpu-bolt" {...props}></Icon>
