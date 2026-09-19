<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6gllbbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6gllbbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:info-octagon" {...props}></Icon>
