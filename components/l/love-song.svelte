<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_mq6qb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_mq6qb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:love-song" {...props}></Icon>
