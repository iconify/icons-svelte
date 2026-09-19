<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_3oub9zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_3oub9zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-hand-sanitizer-spray-virus-block" {...props}></Icon>
