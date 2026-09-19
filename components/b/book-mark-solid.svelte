<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3415pcbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3415pcbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:book-mark-solid" {...props}></Icon>
