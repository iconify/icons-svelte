<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk2hq4bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk2hq4bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:location-plus-solid" {...props}></Icon>
