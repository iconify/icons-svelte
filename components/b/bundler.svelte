<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo0ocib5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":481,"height":512};
const content = `<path class="yo0ocib5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bundler" {...props}></Icon>
