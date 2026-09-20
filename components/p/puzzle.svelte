<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kccvwmb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kccvwmb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:puzzle" {...props}></Icon>
