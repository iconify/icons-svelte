<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt7k6rbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt7k6rbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-luggage-trolleys-beyond-this-point" {...props}></Icon>
