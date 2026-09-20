<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwe3crwea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwe3crwea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-six" {...props}></Icon>
