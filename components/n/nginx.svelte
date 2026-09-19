<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfttfe_2y.css';
import '../../css/t/togmqd0vy.css';
import '../../css/r/rfctt0bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="togmqd0vy"/><path class="rfctt0bky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nginx" {...props}></Icon>
