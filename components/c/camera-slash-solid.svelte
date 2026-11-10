<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd6l3mgky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd6l3mgky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:camera-slash-solid" {...props}></Icon>
