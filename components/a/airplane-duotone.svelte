<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7jxxge6c.css';
import '../../css/v/vnv8itteo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7jxxge6c"/><path clip-rule="evenodd" class="vnv8itteo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:airplane-duotone" {...props}></Icon>
