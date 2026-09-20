<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekpgxptpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ekpgxptpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-harness-and-whistle" {...props}></Icon>
