<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/racr9cchc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="racr9cchc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:refrigeration" {...props}></Icon>
