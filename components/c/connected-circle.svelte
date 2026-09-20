<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbh3tpq0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbh3tpq0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connected-circle" {...props}></Icon>
