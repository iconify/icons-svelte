<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjb7ndb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjb7ndb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-git-2-fill" {...props}></Icon>
