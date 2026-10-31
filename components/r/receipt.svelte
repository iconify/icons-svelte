<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_1hhvbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_1hhvbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:receipt" {...props}></Icon>
