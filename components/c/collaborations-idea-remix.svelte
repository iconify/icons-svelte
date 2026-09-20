<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_fpy7bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a_fpy7bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:collaborations-idea-remix" {...props}></Icon>
