<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jft2-ub9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jft2-ub9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:question-mark-circle-fill" {...props}></Icon>
