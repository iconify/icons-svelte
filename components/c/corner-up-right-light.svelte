<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asgccrulh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="asgccrulh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-right-light" {...props}></Icon>
