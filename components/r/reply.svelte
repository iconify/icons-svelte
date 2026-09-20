<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4orm5d6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v4orm5d6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:reply" {...props}></Icon>
