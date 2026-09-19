<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ygtkpyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q_ygtkpyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-up-chevron-down" {...props}></Icon>
