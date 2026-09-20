<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxhk0c9bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxhk0c9bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-x" {...props}></Icon>
