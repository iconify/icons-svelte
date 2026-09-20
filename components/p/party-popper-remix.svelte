<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhw-h4bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhw-h4bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:party-popper-remix" {...props}></Icon>
