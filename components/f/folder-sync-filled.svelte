<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5bpy3h5o.css';
import '../../css/l/ls7e_sb6t.css';
import '../../css/c/c3wcwvbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5bpy3h5o"/><path class="ls7e_sb6t"/><path class="c3wcwvbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-sync-filled" {...props}></Icon>
