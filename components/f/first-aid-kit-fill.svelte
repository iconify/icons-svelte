<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb6i929xq.css';
import '../../css/i/iea0nmbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb6i929xq"/><path class="iea0nmbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:first-aid-kit-fill" {...props}></Icon>
