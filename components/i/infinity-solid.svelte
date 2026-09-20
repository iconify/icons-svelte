<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3eng5j-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3eng5j-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:infinity-solid" {...props}></Icon>
