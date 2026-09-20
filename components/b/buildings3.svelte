<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgn242ovo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgn242ovo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings3" {...props}></Icon>
