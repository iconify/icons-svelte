<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2gsbjbrx.css';
import '../../css/k/kmot23zoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2gsbjbrx"/><path class="kmot23zoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lock-20" {...props}></Icon>
