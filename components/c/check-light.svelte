<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q39l404xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q39l404xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-light" {...props}></Icon>
