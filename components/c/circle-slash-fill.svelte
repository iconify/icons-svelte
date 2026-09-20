<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to1fr9hry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to1fr9hry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-slash-fill" {...props}></Icon>
