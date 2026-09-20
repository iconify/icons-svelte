<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpbf5qups.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpbf5qups"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudron" {...props}></Icon>
