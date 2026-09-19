<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lor7kcbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lor7kcbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:pill" {...props}></Icon>
