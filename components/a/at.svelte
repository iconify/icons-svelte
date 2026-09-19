<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r37d31ykc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r37d31ykc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:at" {...props}></Icon>
