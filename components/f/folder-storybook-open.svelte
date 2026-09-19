<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/h/hwqg5tbfy.css';
import '../../css/w/wpfh7ntzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="hwqg5tbfy"/><path class="wpfh7ntzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-storybook-open" {...props}></Icon>
