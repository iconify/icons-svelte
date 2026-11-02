<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd4pfqx8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd4pfqx8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-draft-fill" {...props}></Icon>
