<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g01pj538o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g01pj538o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-wide-narrow-solid" {...props}></Icon>
