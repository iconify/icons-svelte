<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilpwgbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilpwgbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-right-line" {...props}></Icon>
