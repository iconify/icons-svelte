<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz16-yb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz16-yb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check-double" {...props}></Icon>
