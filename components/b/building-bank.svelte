<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmu9l7bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmu9l7bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-bank" {...props}></Icon>
