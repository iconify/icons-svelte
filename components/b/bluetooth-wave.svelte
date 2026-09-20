<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qycm1k8wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qycm1k8wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bluetooth-wave" {...props}></Icon>
