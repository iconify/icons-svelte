<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obxvvdc0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obxvvdc0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nas-v2" {...props}></Icon>
