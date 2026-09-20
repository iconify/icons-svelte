<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiefihbpi.css';
import '../../css/d/daoycporf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiefihbpi"/><path class="daoycporf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-clipper-bold" {...props}></Icon>
