<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g87wobb9j.css';
import '../../css/n/nbgk0wbrq.css';
import '../../css/d/dj35aibbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g87wobb9j"/><path class="nbgk0wbrq"/><path class="dj35aibbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:people-nearby-bold" {...props}></Icon>
