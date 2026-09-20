<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s54wg-5dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s54wg-5dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:profile-2user" {...props}></Icon>
