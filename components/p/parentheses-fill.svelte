<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k427guxii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k427guxii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parentheses-fill" {...props}></Icon>
