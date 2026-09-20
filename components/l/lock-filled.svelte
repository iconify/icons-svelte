<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6qmg1rya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6qmg1rya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-filled" {...props}></Icon>
