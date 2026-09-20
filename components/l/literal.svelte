<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8kaz573a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8kaz573a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:literal" {...props}></Icon>
