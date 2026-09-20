<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8kuocjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv8kuocjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:cloud-snow" {...props}></Icon>
