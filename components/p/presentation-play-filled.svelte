<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glgz8bu0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glgz8bu0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:presentation-play-filled" {...props}></Icon>
