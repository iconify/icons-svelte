<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ks6fqtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ks6fqtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinterest-line" {...props}></Icon>
