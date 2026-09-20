<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kamhrtb5g.css';
import '../../css/l/l9ok9ouey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kamhrtb5g"/><path class="l9ok9ouey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cooldown-fill" {...props}></Icon>
