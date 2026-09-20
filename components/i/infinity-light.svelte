<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6-2qkbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-2qkbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:infinity-light" {...props}></Icon>
