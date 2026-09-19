<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmyhv4bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kmyhv4bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-up-left" {...props}></Icon>
