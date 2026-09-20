<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufrkgtbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufrkgtbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-single-outline" {...props}></Icon>
