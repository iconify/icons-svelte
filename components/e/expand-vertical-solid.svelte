<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaxmk38pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxmk38pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:expand-vertical-solid" {...props}></Icon>
