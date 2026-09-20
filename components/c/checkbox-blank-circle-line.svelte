<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aairjvb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aairjvb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:checkbox-blank-circle-line" {...props}></Icon>
