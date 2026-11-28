<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtwqv5btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtwqv5btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:binary-solid" {...props}></Icon>
