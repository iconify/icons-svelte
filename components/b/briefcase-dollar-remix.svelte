<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt4e53b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bt4e53b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:briefcase-dollar-remix" {...props}></Icon>
