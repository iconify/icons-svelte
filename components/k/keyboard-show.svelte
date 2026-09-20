<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe07qvbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe07qvbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:keyboard-show" {...props}></Icon>
