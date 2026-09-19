<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzd7lybys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzd7lybys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-down-left-lg" {...props}></Icon>
