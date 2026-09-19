<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb6fw3bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb6fw3bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:expressionless-face-fill" {...props}></Icon>
