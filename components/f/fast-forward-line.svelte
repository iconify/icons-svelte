<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn0pp-bpg.css';
import '../../css/v/v3kgvknic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0pp-bpg"/><path class="v3kgvknic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fast-forward-line" {...props}></Icon>
