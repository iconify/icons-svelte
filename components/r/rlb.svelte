<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emow59bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emow59bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rlb" {...props}></Icon>
