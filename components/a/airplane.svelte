<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnv8itteo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnv8itteo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:airplane" {...props}></Icon>
