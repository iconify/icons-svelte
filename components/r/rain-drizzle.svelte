<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2h-jqbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2h-jqbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rain-drizzle" {...props}></Icon>
