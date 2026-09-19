<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrb4ktbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="zrb4ktbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mimetype" {...props}></Icon>
