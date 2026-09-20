<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5trom0ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5trom0ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:globe-x-sharp" {...props}></Icon>
