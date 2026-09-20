<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emydz1bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emydz1bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mind" {...props}></Icon>
