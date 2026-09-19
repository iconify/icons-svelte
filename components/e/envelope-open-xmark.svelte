<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhazw7j6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jhazw7j6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:envelope-open-xmark" {...props}></Icon>
