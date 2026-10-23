<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_062c0pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_062c0pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil-line" {...props}></Icon>
