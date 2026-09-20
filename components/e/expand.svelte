<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4_65ebcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4_65ebcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:expand" {...props}></Icon>
