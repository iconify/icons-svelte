<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk_85gb6j.css';
import '../../css/c/czwlbs76f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_85gb6j"/><path class="czwlbs76f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:loading-3-fill" {...props}></Icon>
