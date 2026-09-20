<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdk8ml8uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdk8ml8uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-classic-light" {...props}></Icon>
