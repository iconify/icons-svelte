<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqvvlpb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqvvlpb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-blank-circle-fill" {...props}></Icon>
