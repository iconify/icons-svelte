<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ono7gqb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ono7gqb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x2-sharp" {...props}></Icon>
