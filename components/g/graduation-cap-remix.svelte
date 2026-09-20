<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp91arbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tp91arbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:graduation-cap-remix" {...props}></Icon>
