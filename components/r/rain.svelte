<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9p57bcqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y9p57bcqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:rain" {...props}></Icon>
