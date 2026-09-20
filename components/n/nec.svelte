<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjcozlb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjcozlb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nec" {...props}></Icon>
