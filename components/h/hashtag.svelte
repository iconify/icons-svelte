<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hruhs1bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hruhs1bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hashtag" {...props}></Icon>
