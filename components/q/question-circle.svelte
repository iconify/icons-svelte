<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v847m-bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v847m-bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:question-circle" {...props}></Icon>
