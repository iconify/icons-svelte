<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diz628b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diz628b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-tg" {...props}></Icon>
