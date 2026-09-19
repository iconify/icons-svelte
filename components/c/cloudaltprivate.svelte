<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmmkku4_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="fmmkku4_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudaltprivate" {...props}></Icon>
