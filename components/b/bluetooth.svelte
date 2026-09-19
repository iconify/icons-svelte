<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnn65609l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnn65609l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bluetooth" {...props}></Icon>
