<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1p2s7bsm.css';
import '../../css/g/gb7xzgbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1p2s7bsm"/><path class="gb7xzgbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:calender" {...props}></Icon>
