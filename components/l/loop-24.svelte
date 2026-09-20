<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s99qsccqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s99qsccqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:loop-24" {...props}></Icon>
