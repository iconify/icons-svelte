<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-8dcebhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-8dcebhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-plus-outline" {...props}></Icon>
