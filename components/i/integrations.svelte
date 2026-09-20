<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hexpxuw8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hexpxuw8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:integrations" {...props}></Icon>
