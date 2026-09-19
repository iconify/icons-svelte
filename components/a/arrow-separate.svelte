<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6hm_db6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6hm_db6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-separate" {...props}></Icon>
