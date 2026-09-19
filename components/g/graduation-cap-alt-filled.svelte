<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru5x9fbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru5x9fbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:graduation-cap-alt-filled" {...props}></Icon>
