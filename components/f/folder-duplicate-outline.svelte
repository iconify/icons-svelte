<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbl2mlbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl2mlbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:folder-duplicate-outline" {...props}></Icon>
