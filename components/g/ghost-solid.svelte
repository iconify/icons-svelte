<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqxx1w4em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqxx1w4em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ghost-solid" {...props}></Icon>
