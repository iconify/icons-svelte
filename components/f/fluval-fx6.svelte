<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g28hfjbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g28hfjbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fluval-fx6" {...props}></Icon>
