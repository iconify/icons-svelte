<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzc3xp45p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzc3xp45p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lightbulb-on" {...props}></Icon>
