<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5qw40bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5qw40bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minus-circle-bold" {...props}></Icon>
