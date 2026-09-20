<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oquc4acgh.css';
import '../../css/y/yk5n1ybrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oquc4acgh"/><path class="yk5n1ybrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:feed-light" {...props}></Icon>
