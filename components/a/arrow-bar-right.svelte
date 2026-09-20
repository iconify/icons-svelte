<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5wf4rbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5wf4rbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-right" {...props}></Icon>
