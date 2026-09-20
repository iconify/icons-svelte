<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua86mmb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ua86mmb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:engineer-project-superviser-1-bold" {...props}></Icon>
