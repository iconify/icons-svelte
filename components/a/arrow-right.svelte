<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpswepbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpswepbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-right" {...props}></Icon>
