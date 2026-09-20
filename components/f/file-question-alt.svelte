<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko3zbfbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko3zbfbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-question-alt" {...props}></Icon>
