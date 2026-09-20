<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqgmy6osx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqgmy6osx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coin-3-line" {...props}></Icon>
