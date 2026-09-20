<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1o9flxbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1o9flxbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:not-equal-sign-remix" {...props}></Icon>
