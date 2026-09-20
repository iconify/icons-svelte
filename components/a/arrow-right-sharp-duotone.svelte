<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fksne7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5fksne7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-right-sharp-duotone" {...props}></Icon>
