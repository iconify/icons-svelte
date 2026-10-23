<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6irj2a2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6irj2a2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:banknote-check" {...props}></Icon>
