<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5hrfm07c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5hrfm07c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:inbox-outline" {...props}></Icon>
