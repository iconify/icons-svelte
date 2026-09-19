<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu7zw0bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu7zw0bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:laptop" {...props}></Icon>
