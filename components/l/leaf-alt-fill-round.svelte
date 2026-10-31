<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkt1qo2tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkt1qo2tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:leaf-alt-fill-round" {...props}></Icon>
