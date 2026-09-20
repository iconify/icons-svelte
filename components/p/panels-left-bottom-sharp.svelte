<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eusr_9bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eusr_9bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-left-bottom-sharp" {...props}></Icon>
