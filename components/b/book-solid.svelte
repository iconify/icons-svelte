<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thx0ubc7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="thx0ubc7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:book-solid" {...props}></Icon>
