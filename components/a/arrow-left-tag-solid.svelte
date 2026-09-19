<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh7z8ib8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh7z8ib8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-left-tag-solid" {...props}></Icon>
