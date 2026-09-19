<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1b_p5bbe.css';
import '../../css/o/ogqh4qb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1b_p5bbe"/><path class="ogqh4qb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:boombox-filled" {...props}></Icon>
