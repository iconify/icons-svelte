<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igmn9gypw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="igmn9gypw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:priority-medium-solid" {...props}></Icon>
