<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph17psguc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph17psguc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:question-fill" {...props}></Icon>
