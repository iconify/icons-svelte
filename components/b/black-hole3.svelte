<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv0ph5bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv0ph5bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:black-hole3" {...props}></Icon>
