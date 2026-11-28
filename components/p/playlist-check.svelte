<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk6kzsnsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk6kzsnsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:playlist-check" {...props}></Icon>
