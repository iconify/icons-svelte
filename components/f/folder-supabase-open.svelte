<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mad3lj_un.css';
import '../../css/y/ynyhw8b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mad3lj_un"/><path class="ynyhw8b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-supabase-open" {...props}></Icon>
