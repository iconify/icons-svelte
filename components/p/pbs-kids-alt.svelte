<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr8zurb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr8zurb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pbs-kids-alt" {...props}></Icon>
