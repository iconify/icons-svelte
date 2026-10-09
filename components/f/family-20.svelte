<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-03amqbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b-03amqbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:family-20" {...props}></Icon>
