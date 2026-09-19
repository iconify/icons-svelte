<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpoc_ebsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zpoc_ebsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleh" {...props}></Icon>
