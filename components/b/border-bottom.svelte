<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3hsfibmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3hsfibmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:border-bottom" {...props}></Icon>
