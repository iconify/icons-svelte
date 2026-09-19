<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls7z-wykt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls7z-wykt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:duplicate" {...props}></Icon>
