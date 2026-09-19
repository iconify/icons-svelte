<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z54wf7bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z54wf7bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:checkmark-square-2-fill" {...props}></Icon>
