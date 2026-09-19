<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmn3w7obp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":305,"height":512};
const content = `<path class="jmn3w7obp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:leiningen" {...props}></Icon>
