<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjuw0mb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjuw0mb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:forgejo" {...props}></Icon>
