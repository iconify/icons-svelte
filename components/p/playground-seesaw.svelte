<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4rm54l-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4rm54l-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playground-seesaw" {...props}></Icon>
