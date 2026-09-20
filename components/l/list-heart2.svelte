<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx9gn9bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mx9gn9bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-heart2" {...props}></Icon>
