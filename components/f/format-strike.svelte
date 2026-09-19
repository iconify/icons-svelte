<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffolzo65m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffolzo65m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-strike" {...props}></Icon>
