<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zddm9435c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zddm9435c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:inbox-full-outline" {...props}></Icon>
