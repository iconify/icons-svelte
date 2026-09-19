<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7mehqbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7mehqbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:information-circle" {...props}></Icon>
