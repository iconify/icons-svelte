<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgnnlyb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnnlyb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:domain" {...props}></Icon>
