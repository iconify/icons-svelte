<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_h_9xbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_h_9xbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:puzzle-piece-filled" {...props}></Icon>
