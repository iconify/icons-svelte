<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbpd1jbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbpd1jbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cradle-filled" {...props}></Icon>
