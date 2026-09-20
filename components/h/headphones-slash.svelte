<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsp421byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsp421byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-slash" {...props}></Icon>
