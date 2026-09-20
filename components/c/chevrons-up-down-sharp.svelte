<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivzo09bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivzo09bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-up-down-sharp" {...props}></Icon>
