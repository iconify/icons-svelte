<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz30bjbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz30bjbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-buratto-four" {...props}></Icon>
