<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya858xbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya858xbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:question-mark-square-fill" {...props}></Icon>
