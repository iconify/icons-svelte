<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qknldwu4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qknldwu4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:group" {...props}></Icon>
