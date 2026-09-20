<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_-eynfuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-eynfuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-love-fill" {...props}></Icon>
