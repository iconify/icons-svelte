<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf_48bbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_48bbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:align-right" {...props}></Icon>
