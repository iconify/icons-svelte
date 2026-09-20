<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be6gqg1nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="be6gqg1nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ripple-solid" {...props}></Icon>
