<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq61xm8en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq61xm8en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-arrow-right" {...props}></Icon>
