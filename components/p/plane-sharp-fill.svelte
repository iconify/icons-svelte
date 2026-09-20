<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swhag75sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swhag75sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plane-sharp-fill" {...props}></Icon>
