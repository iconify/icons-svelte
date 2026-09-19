<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq588tbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq588tbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:film-roll-alt-filled" {...props}></Icon>
