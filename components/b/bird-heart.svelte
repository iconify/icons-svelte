<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhae88n8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhae88n8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bird-heart" {...props}></Icon>
