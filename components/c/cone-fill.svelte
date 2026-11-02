<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k963vjbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k963vjbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cone-fill" {...props}></Icon>
