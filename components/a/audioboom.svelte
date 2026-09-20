<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klokvhb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klokvhb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:audioboom" {...props}></Icon>
