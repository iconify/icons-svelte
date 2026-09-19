<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9rl3mb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9rl3mb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:analyze-voice" {...props}></Icon>
