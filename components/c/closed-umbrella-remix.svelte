<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr302bkws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rr302bkws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:closed-umbrella-remix" {...props}></Icon>
