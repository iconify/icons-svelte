<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owpy5-7fq.css';
import '../../css/q/q6421ib4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="owpy5-7fq st1"/><path class="q6421ib4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gitea-wordmark" {...props}></Icon>
