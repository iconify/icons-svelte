<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayp6j3brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayp6j3brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:furrynetwork" {...props}></Icon>
