<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apzc8db8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apzc8db8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-black-hexagons" {...props}></Icon>
