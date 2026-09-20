<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sztb4eboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sztb4eboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-square-bold" {...props}></Icon>
