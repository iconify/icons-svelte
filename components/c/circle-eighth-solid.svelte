<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh5fkfblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh5fkfblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-eighth-solid" {...props}></Icon>
