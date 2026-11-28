<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd7db9bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd7db9bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:microwave" {...props}></Icon>
