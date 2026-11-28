<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3cy-4bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3cy-4bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cherry-solid" {...props}></Icon>
