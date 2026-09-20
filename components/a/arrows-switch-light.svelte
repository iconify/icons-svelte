<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_5nmw-6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_5nmw-6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrows-switch-light" {...props}></Icon>
