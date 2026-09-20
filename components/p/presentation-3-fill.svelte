<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcorcac6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcorcac6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-3-fill" {...props}></Icon>
