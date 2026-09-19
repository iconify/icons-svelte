<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhstl4bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhstl4bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dropbox-solid" {...props}></Icon>
