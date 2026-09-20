<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ulawbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8ulawbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:glass-martini" {...props}></Icon>
