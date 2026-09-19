<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlok4jstc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlok4jstc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:help-square-filled" {...props}></Icon>
