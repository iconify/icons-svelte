<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac09f8epz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac09f8epz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:garage-open-solid" {...props}></Icon>
