<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef1ej922j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ef1ej922j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:microphone-slash-16-solid" {...props}></Icon>
