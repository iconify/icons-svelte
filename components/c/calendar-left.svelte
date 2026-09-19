<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj6ork7js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj6ork7js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-left" {...props}></Icon>
