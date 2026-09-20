<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro266hnbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro266hnbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:branch-solid" {...props}></Icon>
