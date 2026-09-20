<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccfj4q6iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccfj4q6iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:imdb-logo-solid" {...props}></Icon>
