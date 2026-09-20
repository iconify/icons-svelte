<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhpwjz4iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhpwjz4iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:math-norm" {...props}></Icon>
