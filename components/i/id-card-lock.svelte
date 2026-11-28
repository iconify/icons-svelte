<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr8fltb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr8fltb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:id-card-lock" {...props}></Icon>
