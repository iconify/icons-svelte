<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aepfsacgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aepfsacgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plane2" {...props}></Icon>
