<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yypzf8b8r.css';
import '../../css/s/s1altqbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yypzf8b8r"/><path class="s1altqbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-graphql-open" {...props}></Icon>
