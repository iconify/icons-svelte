<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4sn86bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4sn86bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:incognito-fill-round" {...props}></Icon>
