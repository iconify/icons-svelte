<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eelz4jb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eelz4jb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:book-multiple" {...props}></Icon>
