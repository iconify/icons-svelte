<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd8tmirpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd8tmirpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kde-plasma" {...props}></Icon>
