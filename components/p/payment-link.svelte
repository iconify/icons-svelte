<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od9ez2buj.css';
import '../../css/h/hstvx30-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od9ez2buj"/><path class="hstvx30-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:payment-link" {...props}></Icon>
