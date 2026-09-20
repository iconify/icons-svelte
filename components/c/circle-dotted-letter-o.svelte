<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk32wkbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk32wkbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-o" {...props}></Icon>
