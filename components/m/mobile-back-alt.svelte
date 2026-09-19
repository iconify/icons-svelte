<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4ei0bva.css';
import '../../css/n/nd3y8ieci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="nd3y8ieci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-back-alt" {...props}></Icon>
