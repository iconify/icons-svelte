<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxqkl9rnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxqkl9rnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:caret-sort-solid" {...props}></Icon>
