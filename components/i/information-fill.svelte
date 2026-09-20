<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3vptidnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3vptidnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:information-fill" {...props}></Icon>
