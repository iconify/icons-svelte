<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erlzuhi3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erlzuhi3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radar" {...props}></Icon>
